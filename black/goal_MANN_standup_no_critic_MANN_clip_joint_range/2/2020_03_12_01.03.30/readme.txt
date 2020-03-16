n-step: 1
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
reward-scale: 0.1
gating-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 11, 12]
critic-l2-reg: 0.0003
critic-layer-size: [256, 256]
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
joint-interpolation: True
Physics-frequency: 1000
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
render-eval: False
max-episode-num: 5000000
test-num: 4
gating-mask: [[1.0, 1.0]]
replay-buffer-size: 1000000
task-weight: 0.2
env-id: HumanoidBalanceFilter-v0
actor-l2-reg: 0.0003
loss-entropy-coeff: 0.0
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
max-train-time: 10
replay-start-size: 10000
actor-activation-fn: ['relu', 'relu', 'None']
prioritized-exp-replay: True
filter-torque: False
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
LLC-frequency: 500
action-dim: 12
actor-layer-size: [256, 256]
imitation-weight: 0.4
actor-weight-decay: 1e-06
goal-weight: 0.4
gamma: 0.986
interpolation: False
epoch-step-num: 5000000
total-step-num: 2500000000
batch-size: 128
train-step-num: 1
gating-activation-fn: ['relu', 'relu', 'None']
max-step-num: 2500000000
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
record-start-size: 10000.0
max-path-num: 20
actor-lr: 0.0003
max-path-step: 5000
loss-output-diff-coeff: 0
HLC-frequency: 25
replay-ratio: 1
gating-layer-size: [128, 128]
loss-output-bound-coeff: 0.0
expert-num: 2
tau: 0.001
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
epoch-num: 500
bullet-default-PD: False
filter-action: True
squash-action: True
critic-weight-decay: 1e-06
critic-lr: 0.0003
rollout-step-num: 1
dsr-gait-period: 0.6
state-dim: 25
max-test-time: 10
dsr-gait-freq: 1.667
expert-index: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-smooth-coeff: 2.0
