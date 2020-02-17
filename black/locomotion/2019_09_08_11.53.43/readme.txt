state-dim: 23
max-step-num: 2500000000
prioritized-exp-replay: True
Physics-frequency: 1000
critic-l2-reg: 0.0003
critic-lr: 0.0003
actor-activation-fn: ['relu', 'relu', 'None']
max-episode-num: 5000000
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
replay-start-size: 10000
epoch-step-num: 5000000
replay-buffer-size: 1000000
expert-num: 4
n-step: 1
gating-activation-fn: ['relu', 'relu', 'None']
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
tau: 0.001
gamma: 0.955
critic-activation-fn: ['relu', 'relu', 'None']
categorical-distribution: {'v_min': -10, 'n_atoms': 51, 'v_max': 250}
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
dsr-gait-freq: 1.667
actor-weight-decay: 1e-06
actor-layer-size: [256, 256]
imitation-weight: 0.5
train-step-num: 1
bullet-default-PD: False
record-start-size: 10000.0
loss-output-diff-coeff: 0
critic-layer-size: [256, 256]
gating-layer-size: [32, 32]
max-test-time: 10
actor-lr: 0.0003
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
action-dim: 12
max-path-num: 20
loss-output-smooth-coeff: 1.0
gating-index: None
filter-action: True
env-id: HumanoidBalanceFilter-v0
actor-l2-reg: 0.0003
max-train-time: 10
joint-interpolation: True
interpolation: False
total-step-num: 2500000000
HLC-frequency: 25
task-weight: 0.5
reward-scale: 0.1
filter-torque: False
test-num: 4
expert-index: None
batch-size: 128
render-eval: False
max-path-step: 5000
critic-weight-decay: 1e-06
dsr-gait-period: 0.6
epoch-num: 500
loss-entropy-coeff: 0.0
rollout-step-num: 1
squash-action: True
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
LLC-frequency: 500
loss-output-bound-coeff: 0.0
replay-ratio: 1
