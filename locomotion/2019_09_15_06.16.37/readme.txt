interpolation: False
critic-activation-fn: ['relu', 'relu', 'None']
max-path-num: 20
replay-start-size: 10000
prioritized-exp-replay: True
n-step: 1
gating-activation-fn: ['relu', 'relu', 'None']
loss-output-smooth-coeff: 1.0
bullet-default-PD: False
actor-layer-size: [256, 256]
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
loss-entropy-coeff: 0.0
gamma: 0.955
total-step-num: 2500000000
dsr-gait-freq: 1.667
HLC-frequency: 25
critic-l2-reg: 0.0003
env-id: HumanoidBalanceFilter-v0
filter-torque: False
record-start-size: 10000.0
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
actor-lr: 0.0003
train-step-num: 1
max-train-time: 10
test-num: 4
max-step-num: 2500000000
critic-weight-decay: 1e-06
joint-interpolation: True
epoch-num: 500
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
reward-scale: 0.1
replay-ratio: 1
actor-weight-decay: 1e-06
filter-action: True
render-eval: False
expert-num: 4
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
critic-lr: 0.0003
replay-buffer-size: 1000000
LLC-frequency: 500
critic-layer-size: [256, 256]
actor-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
squash-action: True
tau: 0.001
gating-index: None
max-episode-num: 5000000
actor-l2-reg: 0.0003
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
state-dim: 23
loss-output-bound-coeff: 0.0
dsr-gait-period: 0.6
Physics-frequency: 1000
expert-index: None
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
batch-size: 128
max-path-step: 5000
max-test-time: 10
loss-output-diff-coeff: 0
action-dim: 12
rollout-step-num: 1
epoch-step-num: 5000000
task-weight: 0.5
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
imitation-weight: 0.5
